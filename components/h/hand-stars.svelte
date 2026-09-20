<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sua7z4enf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sua7z4enf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:hand-stars" {...props}></Icon>
