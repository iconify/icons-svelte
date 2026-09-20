<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ep5a_vvsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ep5a_vvsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:link-alt" {...props}></Icon>
