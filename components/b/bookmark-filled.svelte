<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apwqmbbzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="apwqmbbzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:bookmark-filled" {...props}></Icon>
