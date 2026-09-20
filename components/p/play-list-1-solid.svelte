<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwt0w3boi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fwt0w3boi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:play-list-1-solid" {...props}></Icon>
