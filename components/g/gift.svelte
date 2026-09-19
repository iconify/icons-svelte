<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8ux-pe8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o8ux-pe8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:gift" {...props}></Icon>
