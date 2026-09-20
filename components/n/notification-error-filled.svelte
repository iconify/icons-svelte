<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsb8z6dli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsb8z6dli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:notification-error-filled" {...props}></Icon>
