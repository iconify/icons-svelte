<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b81cd0uud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="b81cd0uud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:place-of-worship" {...props}></Icon>
