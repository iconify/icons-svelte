<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhekk-bym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bhekk-bym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:programming-filled" {...props}></Icon>
