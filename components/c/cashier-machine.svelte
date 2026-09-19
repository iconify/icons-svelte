<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2ic2kbgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="h2ic2kbgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:cashier-machine" {...props}></Icon>
