<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzwrvcbuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hzwrvcbuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:compass-solid" {...props}></Icon>
