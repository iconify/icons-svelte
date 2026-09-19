<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz3hddb2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="pz3hddb2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:baseball" {...props}></Icon>
