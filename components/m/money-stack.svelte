<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wm219qbsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wm219qbsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:money-stack" {...props}></Icon>
