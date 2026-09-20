<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzo83b3uj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzo83b3uj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:pencil-ruler" {...props}></Icon>
