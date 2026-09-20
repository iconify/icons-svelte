<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra13slu7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ra13slu7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:id" {...props}></Icon>
