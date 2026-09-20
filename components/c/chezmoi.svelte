<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/db4crfb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="db4crfb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:chezmoi" {...props}></Icon>
