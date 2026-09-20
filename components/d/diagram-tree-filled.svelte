<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mojlscbcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mojlscbcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:diagram-tree-filled" {...props}></Icon>
