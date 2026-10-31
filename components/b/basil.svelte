<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9ts_gbgo.css';
import '../../css/e/eve76ufxm.css';
import '../../css/c/crzx6podm.css';
import '../../css/f/fm-1f-6la.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="r9ts_gbgo"/><path class="eve76ufxm"/><path class="crzx6podm"/><path class="fm-1f-6la"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconito:basil" {...props}></Icon>
