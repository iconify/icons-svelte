<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi9pucb8a.css';
import '../../css/y/y008p5b6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fi9pucb8a"/><path clip-rule="evenodd" class="y008p5b6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:gif-light" {...props}></Icon>
