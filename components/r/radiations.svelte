<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epbimrbzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="epbimrbzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:radiations" {...props}></Icon>
