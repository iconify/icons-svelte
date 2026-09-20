<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwvaa_2fz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwvaa_2fz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-arrow-up" {...props}></Icon>
