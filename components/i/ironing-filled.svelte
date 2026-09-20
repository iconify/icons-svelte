<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg6ur5ojt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lg6ur5ojt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ironing-filled" {...props}></Icon>
