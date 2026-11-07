<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iarzmjb8m.css';
import '../../css/g/ge7vrqbtr.css';
import '../../css/l/lxq4dhkod.css';
import '../../css/s/s2-2a1b2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iarzmjb8m"/><path clip-rule="evenodd" class="ge7vrqbtr"/><path class="lxq4dhkod"/><path clip-rule="evenodd" class="s2-2a1b2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:airbuds-right-bold" {...props}></Icon>
