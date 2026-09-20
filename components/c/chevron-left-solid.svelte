<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzk-88c7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mzk-88c7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chevron-left-solid" {...props}></Icon>
