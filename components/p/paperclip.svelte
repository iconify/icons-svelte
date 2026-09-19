<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3muvh5zk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t3muvh5zk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:paperclip" {...props}></Icon>
