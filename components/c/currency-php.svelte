<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm5p7nbqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fm5p7nbqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:currency-php" {...props}></Icon>
