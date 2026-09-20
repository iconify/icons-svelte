<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6zb1ub0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q6zb1ub0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:digg" {...props}></Icon>
