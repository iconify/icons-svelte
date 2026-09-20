<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwr3a161j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nwr3a161j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:geo" {...props}></Icon>
