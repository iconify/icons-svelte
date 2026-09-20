<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zoj4zbc2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zoj4zbc2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:nutanix" {...props}></Icon>
