<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf-gykbkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sf-gykbkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:apple-intelligence" {...props}></Icon>
