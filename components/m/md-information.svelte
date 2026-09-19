<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cetnc8bas.css';
import '../../css/d/d2kx6_b8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cetnc8bas"/><path class="d2kx6_b8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-information" {...props}></Icon>
