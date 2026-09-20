<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whdn7t8on.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="whdn7t8on"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:meh-square-filled" {...props}></Icon>
