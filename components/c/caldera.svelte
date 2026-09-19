<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue6tg1ivu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ue6tg1ivu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:caldera" {...props}></Icon>
