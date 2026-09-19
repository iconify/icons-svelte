<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy2jglbiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xy2jglbiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:ko-ko-kata-box-filled" {...props}></Icon>
