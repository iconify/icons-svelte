<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id5b2zbzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="id5b2zbzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:medical-pack-alt" {...props}></Icon>
