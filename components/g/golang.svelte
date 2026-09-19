<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy4if_byk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="cy4if_byk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:golang" {...props}></Icon>
