<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y75k9vb9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y75k9vb9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:maintenance-warning-filled" {...props}></Icon>
