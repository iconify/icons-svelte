<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s04t-wbch.css';
import '../../css/o/ordjzlbcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s04t-wbch"/><path class="ordjzlbcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-cloudy-night" {...props}></Icon>
