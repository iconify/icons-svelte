<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wziabebtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wziabebtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:propeller-4" {...props}></Icon>
