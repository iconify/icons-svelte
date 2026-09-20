<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sns8z-bqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sns8z-bqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:joyful-filled" {...props}></Icon>
