<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oya9pf1oj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oya9pf1oj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:grasping-slug" {...props}></Icon>
