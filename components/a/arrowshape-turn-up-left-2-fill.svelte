<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hk-o0h0gr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="hk-o0h0gr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrowshape-turn-up-left-2-fill" {...props}></Icon>
