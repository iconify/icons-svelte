<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcbv8hujb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qcbv8hujb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hang-glider" {...props}></Icon>
