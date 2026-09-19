<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6bn8gzzq.css';
import '../../css/y/yo7ggd95z.css';
import '../../css/a/a1qd-mzwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g6bn8gzzq"/><path class="yo7ggd95z"/><path class="a1qd-mzwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-reorder" {...props}></Icon>
