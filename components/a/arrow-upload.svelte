<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc5ozhhhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zc5ozhhhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:arrow-upload" {...props}></Icon>
