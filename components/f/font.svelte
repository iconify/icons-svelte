<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gak5wgbbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gak5wgbbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:font" {...props}></Icon>
