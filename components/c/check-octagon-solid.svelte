<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-yaedc7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-yaedc7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:check-octagon-solid" {...props}></Icon>
