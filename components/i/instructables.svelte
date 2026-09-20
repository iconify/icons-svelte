<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/if8f75qhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="if8f75qhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:instructables" {...props}></Icon>
