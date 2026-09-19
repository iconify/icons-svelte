<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yijvj917a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yijvj917a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:bible" {...props}></Icon>
