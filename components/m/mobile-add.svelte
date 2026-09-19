<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi1fgqnbj.css';
import '../../css/f/fqpkdbsbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bi1fgqnbj"/><path class="fqpkdbsbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:mobile-add" {...props}></Icon>
