<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8p1_8bdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u8p1_8bdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:credit-card-clock" {...props}></Icon>
