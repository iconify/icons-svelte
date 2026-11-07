<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8orc3tyd.css';
import '../../css/u/uy-sggl9k.css';
import '../../css/r/rers1paxa.css';
import '../../css/a/aui-jmtcx.css';
import '../../css/u/uv4oycn3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o8orc3tyd"/><path class="uy-sggl9k"/><path class="rers1paxa"/><path class="aui-jmtcx"/><path class="uv4oycn3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gamepad-no-charge-outline" {...props}></Icon>
