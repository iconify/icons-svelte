<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxumqdb7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lxumqdb7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:reflect" {...props}></Icon>
