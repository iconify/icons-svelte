<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckfku8bhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ckfku8bhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:clock" {...props}></Icon>
