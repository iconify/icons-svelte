<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti1uxtajd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path paint-order="stroke fill markers" class="ti1uxtajd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:quarto" {...props}></Icon>
