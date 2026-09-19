<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osz9gpblp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="osz9gpblp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-restaurant" {...props}></Icon>
