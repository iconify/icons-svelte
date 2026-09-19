<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqc0ucc7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tqc0ucc7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:life-support" {...props}></Icon>
