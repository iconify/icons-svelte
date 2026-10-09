<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-nqb5bcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c-nqb5bcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-loss-20-bold" {...props}></Icon>
