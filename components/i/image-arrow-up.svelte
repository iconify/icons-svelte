<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7qb_tbrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k7qb_tbrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:image-arrow-up" {...props}></Icon>
