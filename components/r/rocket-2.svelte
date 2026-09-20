<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b59ndpb0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b59ndpb0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:rocket-2" {...props}></Icon>
