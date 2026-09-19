<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rs-0-pq3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":715};
const content = `<path class="rs-0-pq3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:plus" {...props}></Icon>
