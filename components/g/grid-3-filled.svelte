<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oav3xe.css';
import '../../css/q/qtbnay.css';
import '../../css/o/o9qm1a.css';
import '../../css/j/jqrlmu.css';
import '../../css/s/so-from-12.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oav3xe qtbnay"/><path class="o9qm1a qtbnay"/><path class="jqrlmu qtbnay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:grid-3-filled" {...props}></Icon>
