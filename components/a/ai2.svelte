<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsnj0do4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jsnj0do4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ai2" {...props}></Icon>
