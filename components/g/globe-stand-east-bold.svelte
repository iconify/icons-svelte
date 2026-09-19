<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sfcsb5sbn.css';
import '../../css/m/mfns35b9r.css';
import '../../css/m/m9mk-kbax.css';
import '../../css/i/i_dr0j9wh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="sfcsb5sbn"/><path class="mfns35b9r"/><path class="m9mk-kbax"/><path clip-rule="evenodd" class="i_dr0j9wh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:globe-stand-east-bold" {...props}></Icon>
