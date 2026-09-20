<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmb_b6brp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmb_b6brp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-up-right" {...props}></Icon>
