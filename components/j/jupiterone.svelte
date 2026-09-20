<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn5qf3ihp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cn5qf3ihp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jupiterone" {...props}></Icon>
