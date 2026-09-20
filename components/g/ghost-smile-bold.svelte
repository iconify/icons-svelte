<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lutq6g-xq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lutq6g-xq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ghost-smile-bold" {...props}></Icon>
