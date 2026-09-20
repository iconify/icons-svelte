<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgi-2-fci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kgi-2-fci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:adblock" {...props}></Icon>
