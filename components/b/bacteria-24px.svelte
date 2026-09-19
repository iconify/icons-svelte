<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuf32_b3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zuf32_b3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:bacteria-24px" {...props}></Icon>
