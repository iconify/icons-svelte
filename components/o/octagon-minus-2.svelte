<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl9f0ocwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tl9f0ocwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:octagon-minus-2" {...props}></Icon>
