<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhj_eqnyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="yhj_eqnyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:important-compact" {...props}></Icon>
