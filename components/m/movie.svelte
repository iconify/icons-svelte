<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcrav4bhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bcrav4bhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:movie" {...props}></Icon>
