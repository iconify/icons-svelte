<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp_zsmb1r.css';
import '../../css/h/hoky06fxe.css';
import '../../css/g/gxeqjdbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tp_zsmb1r"/><circle class="hoky06fxe"/><path class="gxeqjdbdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:admin-outlined" {...props}></Icon>
