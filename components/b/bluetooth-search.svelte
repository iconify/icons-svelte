<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pj7b2nb_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pj7b2nb_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:bluetooth-search" {...props}></Icon>
