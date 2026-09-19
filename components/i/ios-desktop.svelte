<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igbjqgb3u.css';
import '../../css/s/sdwvt0b9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="igbjqgb3u"/><path class="sdwvt0b9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-desktop" {...props}></Icon>
