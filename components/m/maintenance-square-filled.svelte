<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt2e1ccnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gt2e1ccnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:maintenance-square-filled" {...props}></Icon>
