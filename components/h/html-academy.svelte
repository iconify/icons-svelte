<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufsx7q3kd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufsx7q3kd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:html-academy" {...props}></Icon>
