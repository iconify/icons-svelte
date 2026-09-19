<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlg1cmb_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="xlg1cmb_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-turn-down-right" {...props}></Icon>
