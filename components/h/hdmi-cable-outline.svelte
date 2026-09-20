<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/juxektbhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="juxektbhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:hdmi-cable-outline" {...props}></Icon>
