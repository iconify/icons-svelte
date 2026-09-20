<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vswfw9aqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vswfw9aqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:briefcase-outline" {...props}></Icon>
