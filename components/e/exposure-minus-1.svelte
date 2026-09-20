<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w01nvybex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w01nvybex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:exposure-minus-1" {...props}></Icon>
