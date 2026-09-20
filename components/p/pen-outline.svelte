<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_o6jaccl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i_o6jaccl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pen-outline" {...props}></Icon>
