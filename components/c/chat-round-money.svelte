<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkw8ir5gz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tkw8ir5gz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chat-round-money" {...props}></Icon>
