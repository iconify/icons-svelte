<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/ql53qehak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ql53qehak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:numbered-list" {...props}></Icon>
