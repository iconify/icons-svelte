<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo0ecjy4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fo0ecjy4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:4chan" {...props}></Icon>
