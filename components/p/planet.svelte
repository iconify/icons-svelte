<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg50s5vtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gg50s5vtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:planet" {...props}></Icon>
