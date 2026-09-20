<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htkea5bor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="htkea5bor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:flashlight-remix" {...props}></Icon>
