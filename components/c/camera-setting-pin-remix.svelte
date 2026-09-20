<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzg9ihbqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rzg9ihbqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:camera-setting-pin-remix" {...props}></Icon>
