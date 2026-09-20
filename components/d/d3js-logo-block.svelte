<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvzyebcqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tvzyebcqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:d3js-logo-block" {...props}></Icon>
