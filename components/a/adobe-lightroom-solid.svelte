<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xax6l7bwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xax6l7bwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:adobe-lightroom-solid" {...props}></Icon>
