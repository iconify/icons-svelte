<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qy66xwbvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qy66xwbvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:folder-search" {...props}></Icon>
