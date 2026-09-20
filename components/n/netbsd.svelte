<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eelz5c2dj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eelz5c2dj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:netbsd" {...props}></Icon>
