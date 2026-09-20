<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dz_m-jh8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dz_m-jh8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:keg" {...props}></Icon>
