<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5x2r3blr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="p5x2r3blr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-number-sign-small" {...props}></Icon>
