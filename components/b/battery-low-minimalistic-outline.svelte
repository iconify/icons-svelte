<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzibxeopw.css';
import '../../css/o/osemxebgc.css';
import '../../css/o/ocb7_jb-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qzibxeopw"/><path clip-rule="evenodd" class="osemxebgc"/><path class="ocb7_jb-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:battery-low-minimalistic-outline" {...props}></Icon>
