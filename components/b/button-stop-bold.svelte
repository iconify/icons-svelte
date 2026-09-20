<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3dsu-bqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b3dsu-bqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:button-stop-bold" {...props}></Icon>
