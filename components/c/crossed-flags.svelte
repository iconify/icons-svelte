<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rfuc61brw.css';
import '../../css/n/n11ce4bqb.css';
import '../../css/d/dx94qtbnl.css';
import '../../css/d/dtv4i4xpv.css';
import '../../css/t/tt3bc10st.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="rfuc61brw"/><path class="n11ce4bqb"/><path class="dx94qtbnl"/><path class="dtv4i4xpv"/><path class="tt3bc10st"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:crossed-flags" {...props}></Icon>
