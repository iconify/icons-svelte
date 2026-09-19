<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0nf_bbgm.css';
import '../../css/q/q7mu9wb5t.css';
import '../../css/n/ne7rp1b2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0nf_bbgm"/><circle class="q7mu9wb5t"/><path class="ne7rp1b2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:institution" {...props}></Icon>
