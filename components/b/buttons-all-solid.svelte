<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfoen36tg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lfoen36tg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:buttons-all-solid" {...props}></Icon>
