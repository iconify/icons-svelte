<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wn1cvkbsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wn1cvkbsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:better-stack" {...props}></Icon>
