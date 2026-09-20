<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc2ri0bea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="sc2ri0bea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:book-reading" {...props}></Icon>
