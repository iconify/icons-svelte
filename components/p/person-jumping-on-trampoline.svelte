<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0xxf5bby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m0xxf5bby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-jumping-on-trampoline" {...props}></Icon>
