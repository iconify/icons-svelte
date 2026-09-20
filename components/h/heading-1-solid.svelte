<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qejalnb7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qejalnb7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:heading-1-solid" {...props}></Icon>
