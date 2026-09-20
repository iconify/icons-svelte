<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wzno4qqhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wzno4qqhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:open-containers-initiative" {...props}></Icon>
