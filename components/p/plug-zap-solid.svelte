<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf-4ykbht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sf-4ykbht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:plug-zap-solid" {...props}></Icon>
