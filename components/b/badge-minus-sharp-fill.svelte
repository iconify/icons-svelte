<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3htt1wgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t3htt1wgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:badge-minus-sharp-fill" {...props}></Icon>
