<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3n348bsq.css';
import '../../css/r/rh2mivbrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b3n348bsq"/><path class="rh2mivbrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:globe-africa" {...props}></Icon>
