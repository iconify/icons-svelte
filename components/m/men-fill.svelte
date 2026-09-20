<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o39perbfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o39perbfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:men-fill" {...props}></Icon>
