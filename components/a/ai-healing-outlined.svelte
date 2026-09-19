<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3b7b6biu.css';
import '../../css/d/d79oyzb2x.css';
import '../../css/d/d1ym2h3ya.css';
import '../../css/d/d9tmbcbad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m3b7b6biu"/><circle class="d79oyzb2x"/><circle class="d1ym2h3ya"/><path class="d9tmbcbad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:ai-healing-outlined" {...props}></Icon>
