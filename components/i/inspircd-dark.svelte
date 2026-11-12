<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_zka7b9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r_zka7b9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:inspircd-dark" {...props}></Icon>
