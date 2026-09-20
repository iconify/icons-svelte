<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvt-xbsdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tvt-xbsdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:darty" {...props}></Icon>
