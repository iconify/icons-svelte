<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkr13bxin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zkr13bxin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:backward-circle" {...props}></Icon>
