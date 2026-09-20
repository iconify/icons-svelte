<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwhh8jslo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwhh8jslo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:phone-cancel-outline" {...props}></Icon>
