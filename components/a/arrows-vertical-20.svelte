<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wl8q1nb4n.css';
import '../../css/l/l5kfglbol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wl8q1nb4n"/><path class="l5kfglbol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrows-vertical-20" {...props}></Icon>
