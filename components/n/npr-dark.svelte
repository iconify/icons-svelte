<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3k1rzixx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o3k1rzixx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:npr-dark" {...props}></Icon>
