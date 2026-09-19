<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trbai4bzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="trbai4bzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:factory" {...props}></Icon>
