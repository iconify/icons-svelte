<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewm7bp3sn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ewm7bp3sn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:medal-solid" {...props}></Icon>
