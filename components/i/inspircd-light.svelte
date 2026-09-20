<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5kyqgb-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n5kyqgb-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:inspircd-light" {...props}></Icon>
