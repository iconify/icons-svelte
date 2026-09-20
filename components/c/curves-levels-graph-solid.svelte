<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3cf4bbin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s3cf4bbin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:curves-levels-graph-solid" {...props}></Icon>
