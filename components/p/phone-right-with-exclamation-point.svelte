<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm8q8hb9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qm8q8hb9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:phone-right-with-exclamation-point" {...props}></Icon>
