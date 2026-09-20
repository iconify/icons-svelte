<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9wk8624s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s9wk8624s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:johndeere" {...props}></Icon>
