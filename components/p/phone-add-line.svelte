<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0myjwmvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t0myjwmvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:phone-add-line" {...props}></Icon>
