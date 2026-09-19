<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykep8obib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ykep8obib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:drink" {...props}></Icon>
