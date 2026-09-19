<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wes1wgtwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wes1wgtwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:dog" {...props}></Icon>
