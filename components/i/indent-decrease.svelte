<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3eo08bec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x3eo08bec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:indent-decrease" {...props}></Icon>
