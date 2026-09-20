<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcgt-94-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wcgt-94-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:align-right" {...props}></Icon>
