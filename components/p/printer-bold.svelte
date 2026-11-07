<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo34r_bxy.css';
import '../../css/r/rsxgxvbwd.css';
import '../../css/v/vpom7jbce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mo34r_bxy"/><path class="rsxgxvbwd"/><path clip-rule="evenodd" class="vpom7jbce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:printer-bold" {...props}></Icon>
