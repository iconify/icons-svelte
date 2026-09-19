<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh_jiebln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":24};
const content = `<path class="xh_jiebln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:commenting" {...props}></Icon>
