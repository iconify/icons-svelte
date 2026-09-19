<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uagpf0bhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uagpf0bhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:caret-bottom" {...props}></Icon>
