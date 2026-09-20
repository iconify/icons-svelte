<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrpu6pbds.css';
import '../../css/r/rw33ohb9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nrpu6pbds"/><path class="rw33ohb9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:google-plus-square" {...props}></Icon>
