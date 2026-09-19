<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6dze1_pf.css';
import '../../css/v/ved-39bzt.css';
import '../../css/q/qiprivbld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d6dze1_pf"/><path class="ved-39bzt"/><path class="qiprivbld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:bonfire-outline" {...props}></Icon>
