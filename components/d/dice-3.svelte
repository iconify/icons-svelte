<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gn5rlrsrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gn5rlrsrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:dice-3" {...props}></Icon>
