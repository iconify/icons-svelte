<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xr37i9x0n.css';
import '../../css/g/g06w--byr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xr37i9x0n"/><path class="g06w--byr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:rmrk" {...props}></Icon>
