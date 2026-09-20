<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw6t0ac1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fw6t0ac1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:asterisk-octagon-solid" {...props}></Icon>
