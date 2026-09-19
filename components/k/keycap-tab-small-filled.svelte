<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0ft814pq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="i0ft814pq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-tab-small-filled" {...props}></Icon>
