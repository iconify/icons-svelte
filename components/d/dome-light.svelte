<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovyu2kbcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":49,"height":48};
const content = `<path class="ovyu2kbcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:dome-light" {...props}></Icon>
