<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exc70wbnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="exc70wbnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:battery-full-solid" {...props}></Icon>
