<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hf3axfyug.css';
import '../../css/i/ikmyx1evo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="hf3axfyug"/><path clip-rule="evenodd" class="ikmyx1evo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:laravel" {...props}></Icon>
