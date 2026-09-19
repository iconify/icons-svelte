<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hftt3ghvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hftt3ghvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:corner-up-right" {...props}></Icon>
