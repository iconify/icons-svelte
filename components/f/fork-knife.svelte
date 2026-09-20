<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7n261t5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l7n261t5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:fork-knife" {...props}></Icon>
