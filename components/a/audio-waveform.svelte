<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/k/kjrzx5bmv.css';
import '../../css/p/pxw44dr5y.css';
import '../../css/r/r7p23bc9z.css';
import '../../css/f/fm6rnqb2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="kjrzx5bmv wm-shadow"/><path class="pxw44dr5y wm-shadow"/><path class="r7p23bc9z"/><path class="fm6rnqb2m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:audio-waveform" {...props}></Icon>
