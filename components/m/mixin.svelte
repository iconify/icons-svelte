<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6boxob1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":418,"height":512};
const content = `<path class="l6boxob1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:mixin" {...props}></Icon>
