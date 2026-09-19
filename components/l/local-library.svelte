<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdb6pe1ke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":448};
const content = `<path class="pdb6pe1ke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:local-library" {...props}></Icon>
