<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eke_vvbeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eke_vvbeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:dice-refresh" {...props}></Icon>
