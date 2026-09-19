<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz78egceq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pz78egceq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:phone-missed-fill" {...props}></Icon>
