<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvolx0pqg.css';
import '../../css/e/ex_99rxvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qvolx0pqg"/><path class="ex_99rxvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:pimjo-logo" {...props}></Icon>
