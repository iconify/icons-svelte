<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg-mup8zp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jg-mup8zp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:archive-x" {...props}></Icon>
