<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovc2j_bex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovc2j_bex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-c-sharp" {...props}></Icon>
