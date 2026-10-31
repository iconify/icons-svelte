<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/w/weo9vnbgh.css';
import '../../css/d/dv87dmbeo.css';
import '../../css/i/ic9lyt8ds.css';
import '../../css/v/v2g5k0bbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="weo9vnbgh wm-shadow"/><path class="dv87dmbeo wm-shadow"/><path class="ic9lyt8ds"/><path class="v2g5k0bbc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:microwave" {...props}></Icon>
