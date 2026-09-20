<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_t59960j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o_t59960j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:notion-calendar-light" {...props}></Icon>
