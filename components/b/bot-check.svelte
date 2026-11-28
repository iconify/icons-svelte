<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uph89jbvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uph89jbvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bot-check" {...props}></Icon>
