<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb8q_2bvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qb8q_2bvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:groly-dark" {...props}></Icon>
