<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw9st_b5f.css';
import '../../css/f/f7jhyeftq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pw9st_b5f"/><path class="f7jhyeftq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:hcl-light" {...props}></Icon>
