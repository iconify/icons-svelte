<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnhq3rbna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vnhq3rbna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:percent-badge" {...props}></Icon>
