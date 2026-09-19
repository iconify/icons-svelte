<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkzd7kuwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lkzd7kuwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-skip-backward" {...props}></Icon>
