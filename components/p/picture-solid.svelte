<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k80zmcb_e.css';
import '../../css/a/a4jsaxbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k80zmcb_e"/><path class="a4jsaxbri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:picture-solid" {...props}></Icon>
