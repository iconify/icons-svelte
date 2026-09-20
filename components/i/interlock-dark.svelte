<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gu9p88b8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gu9p88b8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:interlock-dark" {...props}></Icon>
