<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-c__p3wy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-c__p3wy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:handle-bottom-right" {...props}></Icon>
