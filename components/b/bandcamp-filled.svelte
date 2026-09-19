<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l51mozblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l51mozblx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:bandcamp-filled" {...props}></Icon>
