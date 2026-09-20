<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwal6xeof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gwal6xeof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:cheveron-up" {...props}></Icon>
