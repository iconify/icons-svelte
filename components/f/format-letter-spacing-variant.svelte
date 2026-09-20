<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp4btfsof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gp4btfsof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-letter-spacing-variant" {...props}></Icon>
