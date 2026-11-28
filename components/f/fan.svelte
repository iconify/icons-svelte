<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehi3mxb4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ehi3mxb4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:fan" {...props}></Icon>
