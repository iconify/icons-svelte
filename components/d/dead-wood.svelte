<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/br43k87zk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="br43k87zk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dead-wood" {...props}></Icon>
