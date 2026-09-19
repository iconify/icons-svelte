<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mw_f-5rvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mw_f-5rvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:info-fill" {...props}></Icon>
