<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s73ludb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s73ludb3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:rollback-outline" {...props}></Icon>
