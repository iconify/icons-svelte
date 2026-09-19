<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs__5j4lh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="cs__5j4lh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:folder" {...props}></Icon>
