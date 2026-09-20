<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fx7ql7bqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fx7ql7bqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:eul" {...props}></Icon>
