<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odoue8rqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="odoue8rqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:hr1" {...props}></Icon>
