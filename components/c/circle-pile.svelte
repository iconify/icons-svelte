<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ty76s9bfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ty76s9bfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:circle-pile" {...props}></Icon>
