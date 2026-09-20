<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dz646ky1a.css';
import '../../css/a/aucdcts6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dz646ky1a"/><path class="aucdcts6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:reaparr-light" {...props}></Icon>
