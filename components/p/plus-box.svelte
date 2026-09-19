<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mns4sqbmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mns4sqbmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:plus-box" {...props}></Icon>
