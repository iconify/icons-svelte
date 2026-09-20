<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mduiahbmo.css';
import '../../css/d/dk-c4yjtp.css';
import '../../css/o/o2ayd2boy.css';
import '../../css/t/tolttpogx.css';
import '../../css/r/rl9y33bwp.css';
import '../../css/w/w7c9bzb2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mduiahbmo"/><path class="dk-c4yjtp"/><path class="o2ayd2boy"/><path class="tolttpogx"/><path class="rl9y33bwp"/><path class="w7c9bzb2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-emojis:e-mail-1" {...props}></Icon>
