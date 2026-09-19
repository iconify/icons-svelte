<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5vo40snv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h5vo40snv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:adobe-indesign-solid" {...props}></Icon>
