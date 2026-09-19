<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kz_94093s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="kz_94093s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:book-bookmark" {...props}></Icon>
