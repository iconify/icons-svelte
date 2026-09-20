<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fus1u3bvc.css';
import '../../css/m/m-g2ynbrd.css';
import '../../css/t/tvdh9jgjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fus1u3bvc"/><path class="m-g2ynbrd"/><path class="tvdh9jgjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-manager" {...props}></Icon>
