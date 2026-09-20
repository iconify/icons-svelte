<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4xdi5bqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v4xdi5bqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:creative-technology" {...props}></Icon>
