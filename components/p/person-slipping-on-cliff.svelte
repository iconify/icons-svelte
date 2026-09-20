<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9zjmsbyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="a9zjmsbyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-slipping-on-cliff" {...props}></Icon>
