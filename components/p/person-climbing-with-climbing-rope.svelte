<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnjhzbbpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qnjhzbbpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-climbing-with-climbing-rope" {...props}></Icon>
