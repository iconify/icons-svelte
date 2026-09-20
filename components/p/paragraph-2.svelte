<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unaz6kbhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="unaz6kbhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:paragraph-2" {...props}></Icon>
