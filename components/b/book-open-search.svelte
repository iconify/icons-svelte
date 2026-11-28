<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eie4fbbal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eie4fbbal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:book-open-search" {...props}></Icon>
