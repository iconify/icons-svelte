<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ors3-zf-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ors3-zf-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-long-up-solid" {...props}></Icon>
