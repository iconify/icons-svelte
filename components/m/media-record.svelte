<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc2r8v-9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bc2r8v-9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:media-record" {...props}></Icon>
