<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3dwbbbwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="z3dwbbbwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:cloud-bolt" {...props}></Icon>
