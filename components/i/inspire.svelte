<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcgo9i_5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qcgo9i_5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:inspire" {...props}></Icon>
