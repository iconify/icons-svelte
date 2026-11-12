<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2_q7l7lm.css';
import '../../css/l/lmsh1d1cc.css';
import '../../css/o/oen_blbax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o2_q7l7lm"/><path class="lmsh1d1cc"/><path class="oen_blbax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:domain-monitor-light" {...props}></Icon>
