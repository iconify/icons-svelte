<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hh9z0bo2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hh9z0bo2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:fidget-spinner" {...props}></Icon>
