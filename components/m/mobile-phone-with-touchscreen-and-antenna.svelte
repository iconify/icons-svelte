<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps6tg9bbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ps6tg9bbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:mobile-phone-with-touchscreen-and-antenna" {...props}></Icon>
