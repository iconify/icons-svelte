<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypl7m5fud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="ypl7m5fud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:arrow-down-wide-short" {...props}></Icon>
