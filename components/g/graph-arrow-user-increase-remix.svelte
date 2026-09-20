<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2r9gabou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o2r9gabou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:graph-arrow-user-increase-remix" {...props}></Icon>
