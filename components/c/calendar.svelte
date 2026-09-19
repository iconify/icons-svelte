<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3c0_-nfk.css';
import '../../css/g/g6i8-p-_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="g3c0_-nfk"/><path class="g6i8-p-_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:calendar" {...props}></Icon>
