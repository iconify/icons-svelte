<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssmc3qbrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ssmc3qbrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:book-open" {...props}></Icon>
