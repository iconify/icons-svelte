<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n91-pkucr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n91-pkucr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:battery-charging" {...props}></Icon>
