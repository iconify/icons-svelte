<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyymwqb4g.css';
import '../../css/t/tpjkktbyw.css';
import '../../css/t/ti2ukbbdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qyymwqb4g"/><path class="tpjkktbyw"/><path class="ti2ukbbdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:goal-24" {...props}></Icon>
