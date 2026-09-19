<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-gpmsb9n.css';
import '../../css/m/mdn6n1b_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-gpmsb9n"/><path class="mdn6n1b_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:link-2-outline" {...props}></Icon>
