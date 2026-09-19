<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lalksfbhk.css';
import '../../css/c/cesl7tgnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lalksfbhk"/><path class="cesl7tgnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-radio-button-on" {...props}></Icon>
