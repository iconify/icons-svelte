<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkbuo_bpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="vkbuo_bpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:car-f" {...props}></Icon>
