<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzgbqj-sb.css';
import '../../css/f/fkpqvet-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hzgbqj-sb"/><path class="fkpqvet-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-briefcase" {...props}></Icon>
