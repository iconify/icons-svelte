<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rerz_fbfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rerz_fbfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:card-pay-fill" {...props}></Icon>
