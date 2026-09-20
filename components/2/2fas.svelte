<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc-g-1byr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lc-g-1byr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:2fas" {...props}></Icon>
