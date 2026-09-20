<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7_jx11ce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7_jx11ce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:enuls" {...props}></Icon>
