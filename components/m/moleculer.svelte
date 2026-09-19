<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrcfhl16j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rrcfhl16j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:moleculer" {...props}></Icon>
