<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prgsuk5uv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="prgsuk5uv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:expand" {...props}></Icon>
