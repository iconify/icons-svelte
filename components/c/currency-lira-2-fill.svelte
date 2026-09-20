<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivfm2ebzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivfm2ebzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-lira-2-fill" {...props}></Icon>
