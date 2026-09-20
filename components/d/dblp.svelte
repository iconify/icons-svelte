<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn9a3fbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jn9a3fbdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:dblp" {...props}></Icon>
