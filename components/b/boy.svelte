<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruak_pb9u.css';
import '../../css/k/k4jt908-j.css';
import '../../css/y/ycq0hybqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ruak_pb9u"/><path class="k4jt908-j"/><path class="ycq0hybqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:boy" {...props}></Icon>
