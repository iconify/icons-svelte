<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcq30tebd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bcq30tebd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:ev-charger-check" {...props}></Icon>
