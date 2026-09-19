<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru5z-ccmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ru5z-ccmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:meh-alt" {...props}></Icon>
