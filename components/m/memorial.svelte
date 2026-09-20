<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/paku0sb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="paku0sb4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:memorial" {...props}></Icon>
