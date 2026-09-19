<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja9-_j11q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ja9-_j11q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:heart-white-suit-circled-small-filled" {...props}></Icon>
