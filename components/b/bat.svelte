<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilpg2j-hn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilpg2j-hn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bat" {...props}></Icon>
