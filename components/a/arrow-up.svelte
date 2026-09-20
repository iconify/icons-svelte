<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4py13b7f.css';
import '../../css/s/s4volvbqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s4py13b7f"/><path class="s4volvbqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:arrow-up" {...props}></Icon>
