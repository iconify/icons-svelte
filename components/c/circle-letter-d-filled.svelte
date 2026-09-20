<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byv9a6byw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="byv9a6byw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-letter-d-filled" {...props}></Icon>
