<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe4uzma3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oe4uzma3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:cssdesignawards" {...props}></Icon>
