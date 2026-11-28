<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgjgwinks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mgjgwinks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:history-x-solid" {...props}></Icon>
