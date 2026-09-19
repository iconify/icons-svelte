<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcadl4bey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qcadl4bey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:corporal" {...props}></Icon>
