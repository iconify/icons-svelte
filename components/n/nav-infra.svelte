<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9lziro0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y9lziro0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:nav-infra" {...props}></Icon>
