<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aiv55sryd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="aiv55sryd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:money" {...props}></Icon>
