<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecxmxhl9m.css';
import '../../css/u/uhv43pf8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ecxmxhl9m"/><path class="uhv43pf8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:plain-3-bold-duotone" {...props}></Icon>
