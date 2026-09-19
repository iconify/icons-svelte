<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xl-6btjno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xl-6btjno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-color-filter-outline" {...props}></Icon>
