<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgsgyebyg.css';
import '../../css/m/mq7oxpbxg.css';
import '../../css/a/ariofzdtp.css';
import '../../css/o/ooetbbcxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mgsgyebyg wm-k"/><path class="mq7oxpbxg wm-a"/><path class="ariofzdtp wm-a"/><path class="ooetbbcxz wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:cast" {...props}></Icon>
