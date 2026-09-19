<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b303i_gmx.css';
import '../../css/s/s70hg-4vd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b303i_gmx"/><path class="s70hg-4vd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-timer-outline" {...props}></Icon>
