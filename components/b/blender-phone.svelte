<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sykjxo4sj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sykjxo4sj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:blender-phone" {...props}></Icon>
