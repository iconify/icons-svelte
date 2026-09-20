<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwejsnb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uwejsnb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-big-right-filled" {...props}></Icon>
