<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqgdw3bnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqgdw3bnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:close-medium-fill" {...props}></Icon>
