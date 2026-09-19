<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7way5tqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7way5tqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:garage-3-prong" {...props}></Icon>
