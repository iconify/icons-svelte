<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isp8llwmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="isp8llwmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:radis" {...props}></Icon>
