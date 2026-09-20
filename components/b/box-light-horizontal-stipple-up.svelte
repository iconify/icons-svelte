<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ciwr-ykht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ciwr-ykht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-horizontal-stipple-up" {...props}></Icon>
