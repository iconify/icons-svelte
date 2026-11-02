<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/x/xs57kdb9i.css';
import '../../css/d/d0dt39byy.css';
import '../../css/l/l4657hg_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="xs57kdb9i"/><path class="d0dt39byy"/><path class="l4657hg_b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:keyboard" {...props}></Icon>
