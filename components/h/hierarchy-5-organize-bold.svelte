<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dx8ltgbmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dx8ltgbmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:hierarchy-5-organize-bold" {...props}></Icon>
