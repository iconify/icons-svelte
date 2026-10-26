<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd3eww85q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bd3eww85q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:health-24px" {...props}></Icon>
