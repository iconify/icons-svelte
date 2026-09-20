<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qimiy-xzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qimiy-xzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:aperture-solid" {...props}></Icon>
