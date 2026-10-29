<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik2cq9xgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ik2cq9xgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:glasses" {...props}></Icon>
