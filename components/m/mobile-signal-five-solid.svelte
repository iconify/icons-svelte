<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gde208bxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gde208bxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:mobile-signal-five-solid" {...props}></Icon>
