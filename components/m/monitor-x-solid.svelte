<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avc904bzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avc904bzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:monitor-x-solid" {...props}></Icon>
