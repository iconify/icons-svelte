<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aze07ox3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aze07ox3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:car" {...props}></Icon>
