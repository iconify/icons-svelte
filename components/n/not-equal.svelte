<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi-5o3bzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bi-5o3bzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:not-equal" {...props}></Icon>
