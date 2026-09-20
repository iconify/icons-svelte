<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gi8prk_nz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gi8prk_nz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:left-right-line" {...props}></Icon>
