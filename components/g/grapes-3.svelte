<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb3ujssrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gb3ujssrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:grapes-3" {...props}></Icon>
