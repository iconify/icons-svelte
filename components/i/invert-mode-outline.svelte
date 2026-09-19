<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w84vznkgo.css';
import '../../css/e/eg1ps4yde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="w84vznkgo"/><path class="eg1ps4yde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:invert-mode-outline" {...props}></Icon>
