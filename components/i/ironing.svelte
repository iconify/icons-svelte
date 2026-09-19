<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tm_49ij3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tm_49ij3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ginetex:ironing" {...props}></Icon>
