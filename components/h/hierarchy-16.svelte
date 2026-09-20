<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm0fz11zk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hm0fz11zk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:hierarchy-16" {...props}></Icon>
