<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rya8k8jhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rya8k8jhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kwsx-radio" {...props}></Icon>
