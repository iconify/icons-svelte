<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_ldur_8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="u_ldur_8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:eps-outline" {...props}></Icon>
