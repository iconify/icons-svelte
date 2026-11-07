<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eiq_gybtr.css';
import '../../css/q/qgwq-wbxv.css';
import '../../css/f/f7ztvmbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eiq_gybtr"/><path class="qgwq-wbxv"/><path class="f7ztvmbgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panels-bottom-right-bold-duotone" {...props}></Icon>
