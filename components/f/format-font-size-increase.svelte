<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywxi7zk5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ywxi7zk5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-font-size-increase" {...props}></Icon>
