<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c70mwuv9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c70mwuv9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:audiobookshelf" {...props}></Icon>
