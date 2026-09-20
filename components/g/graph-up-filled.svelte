<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0136rbvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f0136rbvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:graph-up-filled" {...props}></Icon>
