<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1luhf60p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1luhf60p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:chart-no-axes-combined" {...props}></Icon>
