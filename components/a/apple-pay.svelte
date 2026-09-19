<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9r1unb9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="a9r1unb9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:apple-pay" {...props}></Icon>
