<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epzhw5wxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="epzhw5wxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:border-bottom-plus" {...props}></Icon>
