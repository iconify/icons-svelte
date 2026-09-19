<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqk85vbdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cqk85vbdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:hard-hat" {...props}></Icon>
