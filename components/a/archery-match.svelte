<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngo8wrbzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ngo8wrbzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:archery-match" {...props}></Icon>
