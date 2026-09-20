<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqbvtib-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yqbvtib-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:antgroup" {...props}></Icon>
