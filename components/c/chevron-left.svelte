<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5w5cw75o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s5w5cw75o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:chevron-left" {...props}></Icon>
