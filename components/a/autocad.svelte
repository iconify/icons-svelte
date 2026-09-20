<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvum6ki5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wvum6ki5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:autocad" {...props}></Icon>
