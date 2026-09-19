<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3iqr-btu.css';
import '../../css/l/lalksfbhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j3iqr-btu"/><path class="lalksfbhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-close-circle-outline" {...props}></Icon>
