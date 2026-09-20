<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttgu38bpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ttgu38bpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lms-mixtape-light" {...props}></Icon>
