<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f00tbez2j.css';
import '../../css/e/erolj7bif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f00tbez2j"/><path class="erolj7bif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ironcalc-light" {...props}></Icon>
