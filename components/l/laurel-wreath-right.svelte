<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cufkv7bqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cufkv7bqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:laurel-wreath-right" {...props}></Icon>
