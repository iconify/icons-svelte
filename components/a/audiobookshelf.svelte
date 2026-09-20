<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eoq6qt-ts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eoq6qt-ts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:audiobookshelf" {...props}></Icon>
