<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-7-p6v5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="m-7-p6v5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:block-bell-notification-solid" {...props}></Icon>
