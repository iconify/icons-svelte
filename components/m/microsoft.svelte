<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5vf4le2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5vf4le2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:microsoft" {...props}></Icon>
