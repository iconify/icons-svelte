<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msklz-rvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="msklz-rvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:display-filled" {...props}></Icon>
