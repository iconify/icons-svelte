<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/h/hrjfpsb2u.css';
import '../../css/o/oqdxdpjwb.css';
import '../../css/p/pdzzspcnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="hrjfpsb2u"/><path class="oqdxdpjwb"/><circle class="pdzzspcnx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:percent" {...props}></Icon>
