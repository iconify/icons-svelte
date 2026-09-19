<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq_d5mb3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="iq_d5mb3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:money-yen" {...props}></Icon>
