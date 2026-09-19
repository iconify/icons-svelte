<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_f4g8b1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q_f4g8b1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:arrow-forward-outline" {...props}></Icon>
