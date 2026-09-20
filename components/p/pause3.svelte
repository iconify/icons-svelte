<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo3fzya9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oo3fzya9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:pause3" {...props}></Icon>
