<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ieuaz4n3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ieuaz4n3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:folder-transfer" {...props}></Icon>
