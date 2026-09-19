<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dljy0zzhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dljy0zzhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:border-center" {...props}></Icon>
