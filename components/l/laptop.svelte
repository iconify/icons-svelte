<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jf-i6ybtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":384};
const content = `<path class="jf-i6ybtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:laptop" {...props}></Icon>
