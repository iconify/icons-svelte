<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akhhygbct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="akhhygbct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:italic" {...props}></Icon>
