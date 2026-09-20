<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0q8-_4mw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u0q8-_4mw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:invoice-text-arrow-left" {...props}></Icon>
