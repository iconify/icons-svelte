<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhqprgnjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhqprgnjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chevrons-up-right-solid" {...props}></Icon>
