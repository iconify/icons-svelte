<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rnqi1ebkv.css';
import '../../css/m/mgscpzxqf.css';
import '../../css/n/nw7yc4bui.css';
import '../../css/m/m0mx1pmph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="rnqi1ebkv"/><path class="mgscpzxqf"/><path class="nw7yc4bui"/><path class="m0mx1pmph"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:hourglass-not-done" {...props}></Icon>
