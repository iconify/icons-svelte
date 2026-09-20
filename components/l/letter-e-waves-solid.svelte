<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqwd18b9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dqwd18b9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-e-waves-solid" {...props}></Icon>
