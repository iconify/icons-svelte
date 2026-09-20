<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixc561o8v.css';
import '../../css/q/qrgw_-b1m.css';
import '../../css/b/bc47oi3ue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixc561o8v"/><path class="qrgw_-b1m"/><path class="bc47oi3ue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:duplicate-24" {...props}></Icon>
