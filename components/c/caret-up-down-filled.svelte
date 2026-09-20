<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w06iw6b-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w06iw6b-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:caret-up-down-filled" {...props}></Icon>
