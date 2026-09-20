<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/weh-pb7jy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="weh-pb7jy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:play" {...props}></Icon>
