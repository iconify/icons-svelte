<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwbt9r8zt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mwbt9r8zt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:leaf" {...props}></Icon>
