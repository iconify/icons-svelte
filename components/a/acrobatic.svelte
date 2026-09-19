<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo_-f-osg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zo_-f-osg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:acrobatic" {...props}></Icon>
