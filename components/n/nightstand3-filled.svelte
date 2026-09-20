<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jboz7_tli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jboz7_tli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:nightstand3-filled" {...props}></Icon>
