<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/ekcncrbve.css';
import '../../css/g/gsr7vebbv.css';
import '../../css/w/wz2vvsaic.css';
import '../../css/g/gcmpo3b6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="ekcncrbve"/><path clip-rule="evenodd" class="gsr7vebbv"/><path class="wz2vvsaic"/><path clip-rule="evenodd" class="gcmpo3b6i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flagpack:cc" {...props}></Icon>
