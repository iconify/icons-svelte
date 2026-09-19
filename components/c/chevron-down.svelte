<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcism7j2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="vcism7j2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:chevron-down" {...props}></Icon>
