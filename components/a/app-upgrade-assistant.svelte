<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5t4qho-n.css';
import '../../css/l/lxylry8gl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j5t4qho-n ouiIcon__fillSecondary"/><path class="lxylry8gl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:app-upgrade-assistant" {...props}></Icon>
