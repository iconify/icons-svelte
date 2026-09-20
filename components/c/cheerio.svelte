<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y376512ef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y376512ef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:cheerio" {...props}></Icon>
