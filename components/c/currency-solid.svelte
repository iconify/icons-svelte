<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpt8mwb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mpt8mwb0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:currency-solid" {...props}></Icon>
