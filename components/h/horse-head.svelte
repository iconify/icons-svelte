<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsh_0bvcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="zsh_0bvcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:horse-head" {...props}></Icon>
