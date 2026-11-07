<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6e5-ctfb.css';
import '../../css/i/i3rjp8brq.css';
import '../../css/o/o1g4_ci-r.css';
import '../../css/v/vzn707dmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n6e5-ctfb"/><path class="i3rjp8brq"/><path clip-rule="evenodd" class="o1g4_ci-r"/><path class="vzn707dmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:garage-bold-duotone" {...props}></Icon>
