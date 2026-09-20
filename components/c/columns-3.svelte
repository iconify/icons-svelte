<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b30w9ebxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b30w9ebxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:columns-3" {...props}></Icon>
