<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fa1lvmb-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fa1lvmb-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rewind-forward-circle-bold" {...props}></Icon>
