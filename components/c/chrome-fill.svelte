<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzxy3uu5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yzxy3uu5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chrome-fill" {...props}></Icon>
