<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m84svr34v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m84svr34v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:house-fill" {...props}></Icon>
