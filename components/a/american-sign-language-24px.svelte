<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r18ywyxbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r18ywyxbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:american-sign-language-24px" {...props}></Icon>
