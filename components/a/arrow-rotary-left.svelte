<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4laltbht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d4laltbht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-rotary-left" {...props}></Icon>
