<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/m/mjczpwbmh.css';
import '../../css/g/gr4xe8b9e.css';
import '../../css/h/h79q5vbot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="mjczpwbmh"/><circle class="gr4xe8b9e"/><path class="h79q5vbot"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:outbound" {...props}></Icon>
