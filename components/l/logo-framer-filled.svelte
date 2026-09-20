<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si7uhab_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="si7uhab_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-framer-filled" {...props}></Icon>
