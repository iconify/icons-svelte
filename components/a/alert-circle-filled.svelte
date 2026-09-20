<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntoj3hb7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ntoj3hb7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:alert-circle-filled" {...props}></Icon>
