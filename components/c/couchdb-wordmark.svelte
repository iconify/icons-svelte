<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy6apqb-v.css';
import '../../css/r/ryas737co.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="xy6apqb-v"/><path class="ryas737co"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:couchdb-wordmark" {...props}></Icon>
