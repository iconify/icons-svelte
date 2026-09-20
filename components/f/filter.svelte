<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1wfmlbos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z1wfmlbos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:filter" {...props}></Icon>
