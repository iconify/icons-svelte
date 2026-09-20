<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybiv9vb4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ybiv9vb4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:bell-active" {...props}></Icon>
