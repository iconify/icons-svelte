<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sazs_obtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sazs_obtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:newspaper-star" {...props}></Icon>
