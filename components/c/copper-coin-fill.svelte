<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqorgk93m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqorgk93m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:copper-coin-fill" {...props}></Icon>
