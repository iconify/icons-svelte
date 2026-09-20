<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eu2wbublu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eu2wbublu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:prdotco" {...props}></Icon>
