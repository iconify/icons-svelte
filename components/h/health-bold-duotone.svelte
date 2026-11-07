<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_qncebvw.css';
import '../../css/k/k1jdedccj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_qncebvw"/><path clip-rule="evenodd" class="k1jdedccj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:health-bold-duotone" {...props}></Icon>
