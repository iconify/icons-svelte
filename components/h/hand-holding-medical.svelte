<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2iz5la8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="p2iz5la8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:hand-holding-medical" {...props}></Icon>
