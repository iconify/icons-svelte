<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htcftqbrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="htcftqbrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:file-zip-outline" {...props}></Icon>
