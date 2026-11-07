<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grfgbmbna.css';
import '../../css/d/dt8sml-7w.css';
import '../../css/t/t_-ae6ize.css';
import '../../css/h/h34kibbvp.css';
import '../../css/h/ho4ucccvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="grfgbmbna"/><path class="dt8sml-7w"/><path class="t_-ae6ize"/><path class="h34kibbvp"/><path clip-rule="evenodd" class="ho4ucccvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:playback-speed-outline" {...props}></Icon>
