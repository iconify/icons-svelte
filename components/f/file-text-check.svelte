<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wung1w3oj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wung1w3oj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:file-text-check" {...props}></Icon>
