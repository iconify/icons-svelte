<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cff9kyb6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="cff9kyb6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:external-encoder" {...props}></Icon>
