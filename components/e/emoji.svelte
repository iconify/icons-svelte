<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7fv2d15r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q7fv2d15r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:emoji" {...props}></Icon>
