<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmbubbdlm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cmbubbdlm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:insert-row-solid" {...props}></Icon>
