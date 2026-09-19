<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxbqbtbyf.css';
import '../../css/n/n_ed3d90s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jxbqbtbyf"/><path class="n_ed3d90s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-analytics-outline" {...props}></Icon>
