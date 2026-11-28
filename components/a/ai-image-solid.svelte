<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvk-gab_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kvk-gab_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ai-image-solid" {...props}></Icon>
