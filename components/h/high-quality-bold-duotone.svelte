<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv_hji6de.css';
import '../../css/e/e6boln91d.css';
import '../../css/o/o361r-6gv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pv_hji6de"/><path class="e6boln91d"/><path clip-rule="evenodd" class="o361r-6gv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:high-quality-bold-duotone" {...props}></Icon>
