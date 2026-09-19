<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcwojl0gm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":384};
const content = `<path class="vcwojl0gm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:photo-size-select-small" {...props}></Icon>
