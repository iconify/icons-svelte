<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbmprpz6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="cbmprpz6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:arrow-turn-up" {...props}></Icon>
