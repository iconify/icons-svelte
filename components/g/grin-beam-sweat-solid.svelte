<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ts56i2bjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ts56i2bjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:grin-beam-sweat-solid" {...props}></Icon>
