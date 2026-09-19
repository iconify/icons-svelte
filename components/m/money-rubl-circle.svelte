<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2ot_552a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="g2ot_552a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:money-rubl-circle" {...props}></Icon>
