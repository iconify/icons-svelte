<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uslk_-bhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uslk_-bhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:bold" {...props}></Icon>
