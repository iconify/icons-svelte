<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6lzckbna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w6lzckbna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:github-sponsors" {...props}></Icon>
