<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/joezlabbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="joezlabbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:airbus" {...props}></Icon>
