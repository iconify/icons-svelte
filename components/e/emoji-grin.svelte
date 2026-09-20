<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qh4l7r3-i.css';
import '../../css/k/kne5kebtp.css';
import '../../css/p/p9kwgybhy.css';
import '../../css/o/ox5n37b4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="qh4l7r3-i"/><circle class="kne5kebtp"/><circle class="p9kwgybhy"/><path class="ox5n37b4e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:emoji-grin" {...props}></Icon>
