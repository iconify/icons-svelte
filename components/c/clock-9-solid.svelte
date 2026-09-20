<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muhulxb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="muhulxb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:clock-9-solid" {...props}></Icon>
