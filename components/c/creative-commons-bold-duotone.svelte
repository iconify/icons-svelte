<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv_hji6de.css';
import '../../css/r/rehh5j-gt.css';
import '../../css/v/v9df5cbny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pv_hji6de"/><path class="rehh5j-gt"/><path class="v9df5cbny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:creative-commons-bold-duotone" {...props}></Icon>
