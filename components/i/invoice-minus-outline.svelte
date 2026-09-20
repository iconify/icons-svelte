<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7amtz6os.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7amtz6os"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:invoice-minus-outline" {...props}></Icon>
