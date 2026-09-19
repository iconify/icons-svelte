<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdfm1we6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gdfm1we6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:border-top" {...props}></Icon>
