<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn51s86hr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cn51s86hr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:plane-departure" {...props}></Icon>
