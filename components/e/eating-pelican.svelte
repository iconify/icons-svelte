<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbiaqffpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dbiaqffpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:eating-pelican" {...props}></Icon>
