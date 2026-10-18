<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szahujb-p.css';
import '../../css/o/ocsvobbfk.css';
import '../../css/q/qr12-ubkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="szahujb-p"/><path class="ocsvobbfk"/><path class="qr12-ubkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:contract-for-difference-20" {...props}></Icon>
