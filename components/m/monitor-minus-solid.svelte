<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecsf4pbrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ecsf4pbrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:monitor-minus-solid" {...props}></Icon>
