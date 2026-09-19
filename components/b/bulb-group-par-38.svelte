<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1e3qk_2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k1e3qk_2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bulb-group-par-38" {...props}></Icon>
