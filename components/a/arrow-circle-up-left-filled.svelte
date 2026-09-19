<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pe49jsfsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pe49jsfsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:arrow-circle-up-left-filled" {...props}></Icon>
