<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-13kmb-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-13kmb-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:plane" {...props}></Icon>
