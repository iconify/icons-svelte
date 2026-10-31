<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq8zmfbkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eq8zmfbkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:letter-m-duotone-round" {...props}></Icon>
