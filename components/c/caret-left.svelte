<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unj9eoban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="unj9eoban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:caret-left" {...props}></Icon>
