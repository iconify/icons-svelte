<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkq7-hbwz.css';
import '../../css/z/zwg5l9bqd.css';
import '../../css/q/qy525jbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="jkq7-hbwz"/><path class="zwg5l9bqd"/><path class="qy525jbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:flag-nigeria" {...props}></Icon>
