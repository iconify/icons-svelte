<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wiskg2bdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wiskg2bdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:cloud-moon-showers" {...props}></Icon>
