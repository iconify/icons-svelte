<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrgw_-b1m.css';
import '../../css/b/bc47oi3ue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrgw_-b1m"/><path class="bc47oi3ue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:copy-24" {...props}></Icon>
