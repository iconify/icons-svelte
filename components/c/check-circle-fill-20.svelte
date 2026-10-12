<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0_e6cbmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a0_e6cbmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:check-circle-fill-20" {...props}></Icon>
