<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pj_jv8tuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="pj_jv8tuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:info-solid" {...props}></Icon>
