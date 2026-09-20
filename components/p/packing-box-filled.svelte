<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m45nlgbqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="m45nlgbqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:packing-box-filled" {...props}></Icon>
