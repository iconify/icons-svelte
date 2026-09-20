<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k47pq6b7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k47pq6b7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:poweroff" {...props}></Icon>
