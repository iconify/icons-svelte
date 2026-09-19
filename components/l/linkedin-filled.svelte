<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n66z341rg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n66z341rg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:linkedin-filled" {...props}></Icon>
