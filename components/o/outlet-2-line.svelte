<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b97mt4bgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b97mt4bgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:outlet-2-line" {...props}></Icon>
