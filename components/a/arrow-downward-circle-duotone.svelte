<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmnjdabrt.css';
import '../../css/o/odh8gnbrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zmnjdabrt"/><path class="odh8gnbrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:arrow-downward-circle-duotone" {...props}></Icon>
