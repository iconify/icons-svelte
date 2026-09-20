<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci8vzhbnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ci8vzhbnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:hetzner" {...props}></Icon>
