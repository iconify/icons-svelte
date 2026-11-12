<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0sj-8bcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d0sj-8bcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rallly-light" {...props}></Icon>
