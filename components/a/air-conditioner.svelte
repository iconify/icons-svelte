<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0ugaht_w.css';
import '../../css/d/dbovvfb-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h0ugaht_w"/><path class="dbovvfb-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:air-conditioner" {...props}></Icon>
