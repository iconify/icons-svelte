<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qf0cojxsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qf0cojxsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:ambulance-solid" {...props}></Icon>
