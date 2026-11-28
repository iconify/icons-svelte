<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kslcz4beh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kslcz4beh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-circle-solid" {...props}></Icon>
