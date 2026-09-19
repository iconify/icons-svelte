<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6_pksxpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="s6_pksxpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:capslock-fill" {...props}></Icon>
