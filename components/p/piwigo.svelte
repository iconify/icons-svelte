<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-q3bzbzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-q3bzbzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:piwigo" {...props}></Icon>
