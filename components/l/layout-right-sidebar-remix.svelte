<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sg3-g0s0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sg3-g0s0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:layout-right-sidebar-remix" {...props}></Icon>
