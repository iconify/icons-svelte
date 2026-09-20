<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otue91qts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="otue91qts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:baidu" {...props}></Icon>
