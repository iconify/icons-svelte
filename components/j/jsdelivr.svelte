<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0jc3xb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0jc3xb1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:jsdelivr" {...props}></Icon>
