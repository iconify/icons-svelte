<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5kxlh9of.css';
import '../../css/g/ggo_f5bme.css';
import '../../css/k/khoud0dhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s5kxlh9of"/><path clip-rule="evenodd" class="ggo_f5bme"/><path class="khoud0dhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hiking-minimalistic-bold-duotone" {...props}></Icon>
