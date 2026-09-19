<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x31ta7bfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="x31ta7bfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:multiply" {...props}></Icon>
