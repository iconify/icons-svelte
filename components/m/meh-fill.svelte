<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spo2f0bzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="spo2f0bzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:meh-fill" {...props}></Icon>
