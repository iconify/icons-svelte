<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmp7fsbkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary tmp7fsbkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:omega-duotone" {...props}></Icon>
