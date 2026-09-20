<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xr9j7pbzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xr9j7pbzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:file-export" {...props}></Icon>
