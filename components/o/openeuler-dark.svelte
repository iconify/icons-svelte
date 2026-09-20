<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzd74tzyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hzd74tzyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openeuler-dark" {...props}></Icon>
