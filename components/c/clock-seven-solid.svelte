<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_tsxub1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_tsxub1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:clock-seven-solid" {...props}></Icon>
