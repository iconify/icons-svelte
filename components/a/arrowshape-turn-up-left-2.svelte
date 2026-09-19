<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5e7_6j1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="b5e7_6j1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrowshape-turn-up-left-2" {...props}></Icon>
