<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crxz9v-3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="crxz9v-3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:pause-filled" {...props}></Icon>
