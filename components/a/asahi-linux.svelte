<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox-kjjbac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ox-kjjbac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:asahi-linux" {...props}></Icon>
