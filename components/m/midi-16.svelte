<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iujw47b0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="iujw47b0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:midi-16" {...props}></Icon>
