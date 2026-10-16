<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yexrm9bgt.css';
import '../../css/b/bi3yz8b9a.css';
import '../../css/v/v964ge3ni.css';
import '../../css/h/htwye9bzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yexrm9bgt"/><path class="bi3yz8b9a"/><path class="v964ge3ni"/><path class="htwye9bzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:corn-48-bold" {...props}></Icon>
