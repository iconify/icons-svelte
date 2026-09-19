<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcr93w79u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qcr93w79u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:coronation" {...props}></Icon>
