<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zshw9xbca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zshw9xbca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-right-3" {...props}></Icon>
