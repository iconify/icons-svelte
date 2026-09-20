<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zid9c5b1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zid9c5b1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:glasses-solid" {...props}></Icon>
