<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlrgzl5mj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nlrgzl5mj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nagios-dark" {...props}></Icon>
