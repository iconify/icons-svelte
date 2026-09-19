<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4cutgq5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h4cutgq5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:mouth-outline-24px" {...props}></Icon>
