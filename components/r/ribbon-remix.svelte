<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxu6-3n6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vxu6-3n6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:ribbon-remix" {...props}></Icon>
