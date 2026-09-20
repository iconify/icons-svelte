<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpu_c0btc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tpu_c0btc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:hierarchy-line-1-remix" {...props}></Icon>
