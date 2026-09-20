<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u89-i4iqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u89-i4iqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-open-blank-variant-outline" {...props}></Icon>
