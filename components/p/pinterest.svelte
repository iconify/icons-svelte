<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb1ka5nvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wb1ka5nvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:pinterest" {...props}></Icon>
