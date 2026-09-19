<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2ne70b6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o2ne70b6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:gas-pump" {...props}></Icon>
