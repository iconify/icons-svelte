<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oen2_6b7t.css';
import '../../css/n/nv21e7b0y.css';
import '../../css/a/ao36abnej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="oen2_6b7t"/><circle class="nv21e7b0y"/><path class="ao36abnej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:forkknife" {...props}></Icon>
