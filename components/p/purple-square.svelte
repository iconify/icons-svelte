<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co9mv4w0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="co9mv4w0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:purple-square" {...props}></Icon>
