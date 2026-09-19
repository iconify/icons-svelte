<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3hx6zbdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3hx6zbdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-save" {...props}></Icon>
