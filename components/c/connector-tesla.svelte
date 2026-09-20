<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8b54lbtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t8b54lbtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:connector-tesla" {...props}></Icon>
