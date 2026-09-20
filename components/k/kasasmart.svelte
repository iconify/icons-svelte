<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytwpjybbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ytwpjybbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:kasasmart" {...props}></Icon>
