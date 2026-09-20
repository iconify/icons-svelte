<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w13_1eb6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="w13_1eb6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:clothes-hanger" {...props}></Icon>
