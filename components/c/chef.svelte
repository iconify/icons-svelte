<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvua6pl2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pvua6pl2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:chef" {...props}></Icon>
