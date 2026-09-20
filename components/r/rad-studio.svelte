<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z73hrhjao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z73hrhjao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:rad-studio" {...props}></Icon>
