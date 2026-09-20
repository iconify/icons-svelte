<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frg1mobbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frg1mobbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:new-folder" {...props}></Icon>
