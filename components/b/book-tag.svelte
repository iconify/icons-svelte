<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9xc2yv0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":512};
const content = `<path class="z9xc2yv0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:book-tag" {...props}></Icon>
