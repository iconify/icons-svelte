<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wn64bt0bj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="wn64bt0bj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:round-pushpin-small" {...props}></Icon>
