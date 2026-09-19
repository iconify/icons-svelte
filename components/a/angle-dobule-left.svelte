<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-sd27hth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="x-sd27hth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:angle-dobule-left" {...props}></Icon>
