<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uevno-b1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="uevno-b1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:double-caret-right-outline" {...props}></Icon>
