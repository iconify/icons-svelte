<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fb8mpqbku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="fb8mpqbku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:map" {...props}></Icon>
