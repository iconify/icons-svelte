<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uoduyz_9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="uoduyz_9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:map-alt-3" {...props}></Icon>
