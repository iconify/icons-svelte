<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohqme2bkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ohqme2bkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:battery-vertical-charging-2" {...props}></Icon>
