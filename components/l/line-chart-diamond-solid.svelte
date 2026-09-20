<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uk0t-xb2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uk0t-xb2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:line-chart-diamond-solid" {...props}></Icon>
