<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp7t3jbtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yp7t3jbtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:pyusd" {...props}></Icon>
