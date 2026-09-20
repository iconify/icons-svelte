<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsd-8qpvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="fsd-8qpvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:rack-ipc-success" {...props}></Icon>
