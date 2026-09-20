<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6vn8uk8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q6vn8uk8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:netdata-light" {...props}></Icon>
