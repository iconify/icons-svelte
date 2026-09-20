<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi6ty55tw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oi6ty55tw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:heading-four-solid" {...props}></Icon>
