<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/om0ku_p7k.css';
import '../../css/q/qcq6r3btc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="om0ku_p7k"/><path class="qcq6r3btc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:envelope-paper-document" {...props}></Icon>
