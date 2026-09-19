<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr8zwdb-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kr8zwdb-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:redo" {...props}></Icon>
