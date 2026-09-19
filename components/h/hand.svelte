<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lp9j5qfxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lp9j5qfxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:hand" {...props}></Icon>
