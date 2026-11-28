<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/toc5u-bdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="toc5u-bdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:image-plus-solid" {...props}></Icon>
