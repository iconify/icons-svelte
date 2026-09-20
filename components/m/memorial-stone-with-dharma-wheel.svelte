<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4p8k-bav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m4p8k-bav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:memorial-stone-with-dharma-wheel" {...props}></Icon>
