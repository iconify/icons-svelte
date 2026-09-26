<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj1abhbxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hj1abhbxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:diskette-outline" {...props}></Icon>
