<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le474ol3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="le474ol3r primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:jump-rope-duotone" {...props}></Icon>
