<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh3kbwobr.css';
import '../../css/a/a321_xb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fh3kbwobr"/><path clip-rule="evenodd" class="a321_xb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:data-date-solid" {...props}></Icon>
