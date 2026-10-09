<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw5lpmbnm.css';
import '../../css/d/dm_gb5vkl.css';
import '../../css/v/vi2fl0bal.css';
import '../../css/b/bj-2m5who.css';
import '../../css/l/lkejyhbkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lw5lpmbnm"/><path class="dm_gb5vkl"/><path class="vi2fl0bal"/><path class="bj-2m5who"/><path class="lkejyhbkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:led-48" {...props}></Icon>
