<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr0v5zbta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pr0v5zbta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:restaurant" {...props}></Icon>
