<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yi_pi4bzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yi_pi4bzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:chevron-down-24" {...props}></Icon>
