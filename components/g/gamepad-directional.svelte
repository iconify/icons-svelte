<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkb8q8ewt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hkb8q8ewt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:gamepad-directional" {...props}></Icon>
