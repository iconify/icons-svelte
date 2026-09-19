<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/b/brwuu3bob.css';
import '../../css/f/fhwl3ee0w.css';
import '../../css/q/q1bjnfb8r.css';
import '../../css/v/v9sc_5nqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="brwuu3bob"/><path class="fhwl3ee0w"/><path class="q1bjnfb8r"/><path class="v9sc_5nqm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:qr-code" {...props}></Icon>
