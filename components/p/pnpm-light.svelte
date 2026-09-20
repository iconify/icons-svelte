<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dz6mnac-c.css';
import '../../css/k/k-gdp-2hr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dz6mnac-c"/><path class="k-gdp-2hr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:pnpm-light" {...props}></Icon>
