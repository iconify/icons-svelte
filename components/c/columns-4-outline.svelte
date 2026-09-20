<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in7ea2hci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="in7ea2hci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:columns-4-outline" {...props}></Icon>
