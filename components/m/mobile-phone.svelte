<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf6uoi_3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lf6uoi_3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:mobile-phone" {...props}></Icon>
