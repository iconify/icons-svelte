<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5j38abkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s5j38abkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:hollow-red-circle" {...props}></Icon>
