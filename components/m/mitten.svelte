<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fubfasb6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="fubfasb6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:mitten" {...props}></Icon>
