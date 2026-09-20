<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr53lcc8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cr53lcc8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:meta-logo" {...props}></Icon>
