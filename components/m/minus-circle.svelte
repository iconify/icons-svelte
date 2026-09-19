<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9mrh07zw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e9mrh07zw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:minus-circle" {...props}></Icon>
