<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oh-3m18qq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":352,"height":512};
const content = `<path class="oh-3m18qq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:milkshake" {...props}></Icon>
