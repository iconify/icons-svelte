<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm3tfmb5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cm3tfmb5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:boil-point-outline" {...props}></Icon>
