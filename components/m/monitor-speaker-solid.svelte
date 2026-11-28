<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gk22n923i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gk22n923i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:monitor-speaker-solid" {...props}></Icon>
