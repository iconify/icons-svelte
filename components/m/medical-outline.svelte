<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dh6pq3bmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dh6pq3bmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:medical-outline" {...props}></Icon>
