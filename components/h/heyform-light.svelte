<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7bwm5bym.css';
import '../../css/p/pwgbt_brp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p7bwm5bym"/><path class="pwgbt_brp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:heyform-light" {...props}></Icon>
