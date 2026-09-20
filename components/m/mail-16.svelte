<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v96p-_b2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="v96p-_b2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:mail-16" {...props}></Icon>
