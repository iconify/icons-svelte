<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bboyc8n1g.css';
import '../../css/p/p3hvddcql.css';
import '../../css/r/rgcaz9bqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><rect class="bboyc8n1g"/><path class="p3hvddcql"/><path class="rgcaz9bqd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:bed-empty" {...props}></Icon>
