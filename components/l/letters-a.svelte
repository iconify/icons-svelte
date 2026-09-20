<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yla7ipb-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yla7ipb-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:letters-a" {...props}></Icon>
