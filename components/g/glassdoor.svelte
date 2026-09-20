<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9_2shbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m9_2shbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:glassdoor" {...props}></Icon>
