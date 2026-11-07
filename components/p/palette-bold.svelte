<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_09h_bys.css';
import '../../css/r/r62on_nvj.css';
import '../../css/v/v_ckypzwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x_09h_bys"/><path class="r62on_nvj"/><path class="v_ckypzwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:palette-bold" {...props}></Icon>
