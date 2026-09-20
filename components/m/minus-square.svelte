<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3z_mu5px.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r3z_mu5px"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:minus-square" {...props}></Icon>
