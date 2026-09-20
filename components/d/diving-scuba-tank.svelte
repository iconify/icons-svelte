<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6r9v-bax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c6r9v-bax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:diving-scuba-tank" {...props}></Icon>
