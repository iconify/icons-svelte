<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h20n09zle.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h20n09zle"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bank-circle" {...props}></Icon>
