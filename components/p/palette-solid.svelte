<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a268_s4rr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a268_s4rr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:palette-solid" {...props}></Icon>
