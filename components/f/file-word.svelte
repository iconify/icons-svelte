<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktoz517ix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="ktoz517ix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:file-word" {...props}></Icon>
