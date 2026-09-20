<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcv7dgnpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tcv7dgnpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hdhomerun-light" {...props}></Icon>
