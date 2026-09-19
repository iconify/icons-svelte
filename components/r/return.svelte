<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irv06objy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="irv06objy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:return" {...props}></Icon>
