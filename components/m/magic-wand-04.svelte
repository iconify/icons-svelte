<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag2u3nb2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ag2u3nb2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:magic-wand-04" {...props}></Icon>
