<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab6ek4sun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ab6ek4sun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:edit-alt" {...props}></Icon>
