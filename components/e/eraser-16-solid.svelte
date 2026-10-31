<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqqsx8htq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cqqsx8htq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:eraser-16-solid" {...props}></Icon>
