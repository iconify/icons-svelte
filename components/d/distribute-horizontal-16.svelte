<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyu98sybs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xyu98sybs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:distribute-horizontal-16" {...props}></Icon>
