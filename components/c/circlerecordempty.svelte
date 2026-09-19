<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0vm4nbxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="z0vm4nbxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circlerecordempty" {...props}></Icon>
