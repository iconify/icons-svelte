<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2n1_ac4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n2n1_ac4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-imac" {...props}></Icon>
