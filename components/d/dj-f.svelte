<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys8sjua-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-2};
const content = `<path class="ys8sjua-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:dj-f" {...props}></Icon>
