<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/voor-mbwk.css';
import '../../css/b/bxxuiebbd.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 voor-mbwk"/><circle class="bxxuiebbd clr-i-solid clr-i-solid-path-2" transform="rotate(-9.22 17.955 18.05)"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:atom-solid" {...props}></Icon>
