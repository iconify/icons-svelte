<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cna79bboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cna79bboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:command-palette-24" {...props}></Icon>
