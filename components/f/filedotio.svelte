<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1pa38b9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1pa38b9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:filedotio" {...props}></Icon>
