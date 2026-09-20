<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljt8zg9xj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ljt8zg9xj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:linkstack-dark" {...props}></Icon>
