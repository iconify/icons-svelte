<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6qqvlb9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":700,"height":677};
const content = `<path class="k6qqvlb9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:checkbox" {...props}></Icon>
