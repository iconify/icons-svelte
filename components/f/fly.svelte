<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3fw_60vu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k3fw_60vu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fly" {...props}></Icon>
