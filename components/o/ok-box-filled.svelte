<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iub-4pq8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="iub-4pq8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:ok-box-filled" {...props}></Icon>
