<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ig8ga7b3p.css';
import '../../css/r/r-u6g9bnb.css';
import '../../css/s/s1gudszho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ig8ga7b3p"/><path class="r-u6g9bnb"/><path class="s1gudszho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bottle-bold-duotone" {...props}></Icon>
