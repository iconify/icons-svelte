<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7znt3bmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n7znt3bmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:mathematics-display-block" {...props}></Icon>
