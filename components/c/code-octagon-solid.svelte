<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nakui0b-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nakui0b-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:code-octagon-solid" {...props}></Icon>
