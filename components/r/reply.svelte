<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxh3-5bmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fxh3-5bmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:reply" {...props}></Icon>
