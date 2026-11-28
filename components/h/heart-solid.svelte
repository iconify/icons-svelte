<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vj2wag31f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vj2wag31f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:heart-solid" {...props}></Icon>
