<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dto3afbko.css';
import '../../css/o/o_eh4ib9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dto3afbko"/><path class="o_eh4ib9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:health-blood-drop-type" {...props}></Icon>
