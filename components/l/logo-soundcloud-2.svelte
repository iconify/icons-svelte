<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhxtm0v3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uhxtm0v3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:logo-soundcloud-2" {...props}></Icon>
