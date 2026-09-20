<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e07hwbb_f.css';
import '../../css/j/jjlq6dbda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e07hwbb_f"/><path class="jjlq6dbda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:adventurelog-light" {...props}></Icon>
