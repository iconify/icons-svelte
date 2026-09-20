<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj9zj5eja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bj9zj5eja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:life-jacket" {...props}></Icon>
