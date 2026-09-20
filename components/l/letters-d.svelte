<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2aa21p0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w2aa21p0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:letters-d" {...props}></Icon>
