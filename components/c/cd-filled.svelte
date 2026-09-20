<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj6zuzb8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uj6zuzb8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cd-filled" {...props}></Icon>
