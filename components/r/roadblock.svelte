<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scx9qjbjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="scx9qjbjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:roadblock" {...props}></Icon>
