<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwsr-b07g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hwsr-b07g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:quit-full-screen-outline" {...props}></Icon>
