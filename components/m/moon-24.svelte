<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxse9ubls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cxse9ubls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:moon-24" {...props}></Icon>
