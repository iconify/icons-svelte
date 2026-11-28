<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2_mlhb6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2_mlhb6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:network-gear" {...props}></Icon>
