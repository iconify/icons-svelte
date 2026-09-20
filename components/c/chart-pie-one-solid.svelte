<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx9tpwuxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sx9tpwuxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chart-pie-one-solid" {...props}></Icon>
