<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2217gn1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2217gn1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:beaker-alert" {...props}></Icon>
