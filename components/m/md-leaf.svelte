<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lga59ib1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lga59ib1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-leaf" {...props}></Icon>
