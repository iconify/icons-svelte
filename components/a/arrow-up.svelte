<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/p/peqw2v4yq.css';
import '../../css/l/lwwq5jbxt.css';
import '../../css/o/oc3xhs8uk.css';
import '../../css/s/sm00ukm5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="peqw2v4yq wm-shadow"/><path class="lwwq5jbxt wm-shadow"/><path class="oc3xhs8uk"/><path class="sm00ukm5a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:arrow-up" {...props}></Icon>
