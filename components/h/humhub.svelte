<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc2x0wbhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xc2x0wbhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:humhub" {...props}></Icon>
