<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3lttot3l.css';
import '../../css/m/mf2faab1e.css';
import '../../css/i/igmy_9b_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r3lttot3l"/><path class="mf2faab1e"/><path class="igmy_9b_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:more-3-line" {...props}></Icon>
