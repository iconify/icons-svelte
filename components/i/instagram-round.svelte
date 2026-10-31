<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyah5ibdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yyah5ibdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:instagram-round" {...props}></Icon>
