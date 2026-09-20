<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6v2n9a-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i6v2n9a-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:kling" {...props}></Icon>
