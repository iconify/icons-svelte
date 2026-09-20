<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b___i6bwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b___i6bwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:arrows-left-down" {...props}></Icon>
