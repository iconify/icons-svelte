<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt-7dbckp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jt-7dbckp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:babelio" {...props}></Icon>
