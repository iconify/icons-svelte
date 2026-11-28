<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7b_szke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sv7b_szke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:coin-plus" {...props}></Icon>
