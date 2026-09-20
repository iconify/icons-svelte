<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0a3z3bzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c0a3z3bzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:radar3-filled" {...props}></Icon>
