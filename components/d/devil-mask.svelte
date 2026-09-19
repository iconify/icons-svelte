<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcxkmt8kn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qcxkmt8kn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:devil-mask" {...props}></Icon>
