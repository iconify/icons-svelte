<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av4w2sb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="av4w2sb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:arrow-left-thick" {...props}></Icon>
