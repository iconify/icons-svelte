<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uinxx6akt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uinxx6akt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:book-close" {...props}></Icon>
