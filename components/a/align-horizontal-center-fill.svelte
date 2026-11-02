<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk7vp6b9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pk7vp6b9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-horizontal-center-fill" {...props}></Icon>
