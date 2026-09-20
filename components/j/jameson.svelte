<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml2zg-koh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ml2zg-koh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:jameson" {...props}></Icon>
