<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgoaobaxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lgoaobaxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:a-arrow-up-solid" {...props}></Icon>
