<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/os67eymuh.css';
import '../../css/s/sg7qdup6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="os67eymuh"/><path class="sg7qdup6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:rain" {...props}></Icon>
