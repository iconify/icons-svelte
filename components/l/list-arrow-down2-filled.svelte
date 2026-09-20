<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gi70tsboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gi70tsboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:list-arrow-down2-filled" {...props}></Icon>
