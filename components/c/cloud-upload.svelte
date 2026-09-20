<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fheo4objp.css';
import '../../css/p/p8bzevp-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fheo4objp"/><path class="p8bzevp-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:cloud-upload" {...props}></Icon>
