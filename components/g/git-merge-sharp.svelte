<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zx5n8lb2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zx5n8lb2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:git-merge-sharp" {...props}></Icon>
