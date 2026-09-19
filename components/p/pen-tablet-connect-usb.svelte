<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/o/o-ykjtgrt.css';
import '../../css/q/qhf8v1bth.css';
import '../../css/i/iu5m-vbcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="o-ykjtgrt"/><path class="qhf8v1bth"/><path class="iu5m-vbcs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:pen-tablet-connect-usb" {...props}></Icon>
