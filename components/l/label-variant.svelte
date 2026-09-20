<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sj2firt2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sj2firt2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:label-variant" {...props}></Icon>
