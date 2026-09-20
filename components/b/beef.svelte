<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/y/yc12vib0p.css';
import '../../css/g/g9cw18bkp.css';
import '../../css/d/dlsp10brj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yc12vib0p"/><path class="g9cw18bkp"/><circle class="dlsp10brj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:beef" {...props}></Icon>
