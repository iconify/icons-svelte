<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xass45b8v.css';
import '../../css/j/jww6vuirk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xass45b8v"/><path class="jww6vuirk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:location-duotone" {...props}></Icon>
