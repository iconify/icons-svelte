<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a23t4i8qj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":24};
const content = `<path class="a23t4i8qj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:git" {...props}></Icon>
