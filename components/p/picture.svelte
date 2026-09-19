<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh7bkobdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<path class="yh7bkobdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:picture" {...props}></Icon>
