<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8o49bcjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="p8o49bcjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:form-library-mirrored" {...props}></Icon>
