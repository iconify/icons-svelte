<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqt_2kuii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mqt_2kuii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bagel-solid" {...props}></Icon>
