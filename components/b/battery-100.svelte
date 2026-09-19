<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8k9ylbgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o8k9ylbgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:battery-100" {...props}></Icon>
