<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lftu6m2lk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lftu6m2lk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:banner" {...props}></Icon>
