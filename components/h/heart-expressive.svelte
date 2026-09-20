<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5zindb7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a5zindb7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:heart-expressive" {...props}></Icon>
