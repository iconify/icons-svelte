<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2yryw4aw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i2yryw4aw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:button-fast-forward-2-solid" {...props}></Icon>
