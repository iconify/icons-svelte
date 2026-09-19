<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obshxodmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="obshxodmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:jigsaw-puzzle-piece-small" {...props}></Icon>
