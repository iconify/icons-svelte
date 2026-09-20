<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k98if7bxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k98if7bxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:bookmark-filled" {...props}></Icon>
