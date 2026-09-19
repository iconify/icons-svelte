<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbz05ihlt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="mbz05ihlt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:ioxhost" {...props}></Icon>
