<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly8h1kbew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ly8h1kbew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:amazoniam" {...props}></Icon>
