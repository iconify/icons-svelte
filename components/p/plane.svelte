<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxhzv1nnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lxhzv1nnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:plane" {...props}></Icon>
