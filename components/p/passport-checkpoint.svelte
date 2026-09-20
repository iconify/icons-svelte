<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhdzl1b5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vhdzl1b5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:passport-checkpoint" {...props}></Icon>
