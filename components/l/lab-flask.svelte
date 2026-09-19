<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3b_oab5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="e3b_oab5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:lab-flask" {...props}></Icon>
