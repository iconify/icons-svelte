<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n87-j9aso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n87-j9aso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:inbox-arrow-right" {...props}></Icon>
