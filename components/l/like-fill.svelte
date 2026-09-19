<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqo0f6boq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wqo0f6boq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:like-fill" {...props}></Icon>
