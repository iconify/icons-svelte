<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a73f9-bto.css';
import '../../css/w/w8e4zs4sx.css';
import '../../css/w/w5hp-fb7h.css';
import '../../css/h/hxu-4ufpy.css';
import '../../css/k/k-319-kjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a73f9-bto"/><path class="w8e4zs4sx"/><path class="w5hp-fb7h"/><path class="hxu-4ufpy"/><path class="k-319-kjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cobb-angle" {...props}></Icon>
