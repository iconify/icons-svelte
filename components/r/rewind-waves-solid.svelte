<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy59z_kqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xy59z_kqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:rewind-waves-solid" {...props}></Icon>
