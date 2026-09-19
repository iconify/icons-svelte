<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvalutb3t.css';
import '../../css/e/eqdsrrcni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="qvalutb3t"/><path class="eqdsrrcni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-patreon" {...props}></Icon>
