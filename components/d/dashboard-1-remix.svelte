<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf1mlabzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sf1mlabzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:dashboard-1-remix" {...props}></Icon>
