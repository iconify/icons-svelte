<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebc0syb4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ebc0syb4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-long-right-solid" {...props}></Icon>
