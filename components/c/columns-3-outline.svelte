<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng4igtd1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ng4igtd1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:columns-3-outline" {...props}></Icon>
